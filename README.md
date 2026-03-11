# Server Metrics 2026-03-11 00:36:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36542.9 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789000
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 9007
telemt_upstream_connect_attempt_total 7959
telemt_upstream_connect_success_total 7950
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 17720
telemt_me_reconnect_success_total 6055
telemt_me_reader_eof_total 6640
telemt_me_idle_close_by_peer_total 6640
telemt_me_route_drop_no_conn_total 325235
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746807
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3556
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2562
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6468
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6049
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 746584
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 10410318152 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 222818430660 (207.52 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36599.5 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340452
telemt_connections_bad_total 2384
telemt_handshake_timeouts_total 17634
telemt_upstream_connect_attempt_total 14975
telemt_upstream_connect_success_total 12096
telemt_upstream_connect_fail_total 2879
telemt_upstream_connect_attempts_per_request{bucket="1"} 14975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2879
telemt_me_keepalive_timeout_total 1705
telemt_me_reconnect_attempts_total 8100
telemt_me_reconnect_success_total 7287
telemt_me_reader_eof_total 7684
telemt_me_idle_close_by_peer_total 7682
telemt_me_route_drop_no_conn_total 172289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289894
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1754
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 1260
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7386
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7266
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 292163
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 2831140290 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 70115676652 (65.30 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36599.3 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566052
telemt_connections_bad_total 3885
telemt_handshake_timeouts_total 34081
telemt_upstream_connect_attempt_total 10044
telemt_upstream_connect_success_total 9905
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 10044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 18029
telemt_me_reconnect_success_total 6967
telemt_me_reader_eof_total 7603
telemt_me_idle_close_by_peer_total 7603
telemt_me_route_drop_no_conn_total 194621
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 7409
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6956
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 500493
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 6816968605 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 153922939905 (143.35 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36599.9 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413268
telemt_connections_bad_total 34857
telemt_handshake_timeouts_total 38711
telemt_upstream_connect_attempt_total 10426
telemt_upstream_connect_success_total 10426
telemt_upstream_connect_attempts_per_request{bucket="1"} 10426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 401
telemt_me_reconnect_attempts_total 9595
telemt_me_reconnect_success_total 8562
telemt_me_reader_eof_total 9046
telemt_me_idle_close_by_peer_total 9046
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 127633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326684
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 8678
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8546
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 326360
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 4189700656 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 90545517720 (84.33 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36599.5 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437353
telemt_connections_bad_total 4140
telemt_handshake_timeouts_total 2756
telemt_upstream_connect_attempt_total 11059
telemt_upstream_connect_success_total 11014
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 11059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 12883
telemt_me_reconnect_success_total 9117
telemt_me_reader_eof_total 9587
telemt_me_idle_close_by_peer_total 9587
telemt_me_route_drop_no_conn_total 146346
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403275
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2270
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 9352
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9117
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 403014
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 8349341872 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 145933585240 (135.91 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 36
```