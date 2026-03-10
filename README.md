# Server Metrics 2026-03-10 23:50:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33800.3 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769736
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 8554
telemt_upstream_connect_attempt_total 7335
telemt_upstream_connect_success_total 7326
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 462
telemt_me_reconnect_attempts_total 17225
telemt_me_reconnect_success_total 5563
telemt_me_reader_eof_total 6112
telemt_me_idle_close_by_peer_total 6112
telemt_me_route_drop_no_conn_total 318655
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3523
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 2539
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 1314
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5973
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5557
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 728655
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 10142522168 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 217430631544 (202.50 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33857.1 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333169
telemt_connections_bad_total 2381
telemt_handshake_timeouts_total 17615
telemt_upstream_connect_attempt_total 14212
telemt_upstream_connect_success_total 11336
telemt_upstream_connect_fail_total 2876
telemt_upstream_connect_attempts_per_request{bucket="1"} 14212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2876
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 7469
telemt_me_reconnect_success_total 6657
telemt_me_reader_eof_total 7012
telemt_me_idle_close_by_peer_total 7010
telemt_me_route_drop_no_conn_total 170501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282819
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6752
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6636
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 285088
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2774821966 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 69124443308 (64.38 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33856.8 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552891
telemt_connections_bad_total 3689
telemt_handshake_timeouts_total 33993
telemt_upstream_connect_attempt_total 9172
telemt_upstream_connect_success_total 9045
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 9172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 17299
telemt_me_reconnect_success_total 6242
telemt_me_reader_eof_total 6839
telemt_me_idle_close_by_peer_total 6839
telemt_me_route_drop_no_conn_total 191212
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486738
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6680
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6231
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 487663
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 6760927921 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 152293562021 (141.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33857.3 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398401
telemt_connections_bad_total 32353
telemt_handshake_timeouts_total 36767
telemt_upstream_connect_attempt_total 9485
telemt_upstream_connect_success_total 9485
telemt_upstream_connect_attempts_per_request{bucket="1"} 9485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 391
telemt_me_reconnect_attempts_total 8783
telemt_me_reconnect_success_total 7755
telemt_me_reader_eof_total 8174
telemt_me_idle_close_by_peer_total 8174
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 124936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7868
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7740
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 316000
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 4100687572 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 88964031620 (82.85 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33857.0 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421862
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2690
telemt_upstream_connect_attempt_total 10308
telemt_upstream_connect_success_total 10268
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 12266
telemt_me_reconnect_success_total 8503
telemt_me_reader_eof_total 8932
telemt_me_idle_close_by_peer_total 8932
telemt_me_route_drop_no_conn_total 143426
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390857
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2246
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8734
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8503
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 390633
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 6538877132 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 143470314052 (133.62 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 32
```