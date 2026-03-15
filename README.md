# Server Metrics 2026-03-15 10:35:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 44459.7 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086233
telemt_connections_bad_total 65276
telemt_handshake_timeouts_total 8451
telemt_upstream_connect_attempt_total 8971
telemt_upstream_connect_success_total 8932
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7923
telemt_me_reconnect_success_total 6699
telemt_me_reader_eof_total 7112
telemt_me_idle_close_by_peer_total 7112
telemt_me_route_drop_no_conn_total 360276
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916916
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3364
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 2415
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6833
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 6688
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 916911
telemt_user_connections_current{user="hello"} 2129
telemt_user_octets_from_client{user="hello"} 13112699344 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 361625447972 (336.79 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 44460.4 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427380
telemt_connections_bad_total 23485
telemt_handshake_timeouts_total 17889
telemt_upstream_connect_attempt_total 11813
telemt_upstream_connect_success_total 11750
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 11813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9248
telemt_me_reconnect_success_total 9190
telemt_me_reader_eof_total 9720
telemt_me_idle_close_by_peer_total 9720
telemt_me_route_drop_no_conn_total 109034
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337944
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1195
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 780
telemt_desync_frames_bucket_total{bucket="1_2"} 402
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9279
telemt_me_writer_restored_same_endpoint_total 9182
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 338230
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 4912080191 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 126987998704 (118.27 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 44460.4 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815910
telemt_connections_bad_total 27100
telemt_handshake_timeouts_total 80679
telemt_upstream_connect_attempt_total 9881
telemt_upstream_connect_success_total 9839
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 7641
telemt_me_reconnect_success_total 7591
telemt_me_reader_eof_total 8040
telemt_me_idle_close_by_peer_total 8040
telemt_me_route_drop_no_conn_total 225192
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593494
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1335
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7691
telemt_me_writer_restored_same_endpoint_total 7572
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 592912
telemt_user_connections_current{user="hello"} 1246
telemt_user_octets_from_client{user="hello"} 8723026040 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 235939538628 (219.74 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 44460.3 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445145
telemt_connections_bad_total 56243
telemt_handshake_timeouts_total 25668
telemt_upstream_connect_attempt_total 13365
telemt_upstream_connect_success_total 13030
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 13365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31154
telemt_me_reconnect_success_total 10791
telemt_me_reader_eof_total 11753
telemt_me_idle_close_by_peer_total 11753
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 124153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334534
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 791
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11526
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10759
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 334444
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 4027054852 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 107172873016 (99.81 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 44461.5 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450738
telemt_connections_bad_total 6150
telemt_handshake_timeouts_total 7538
telemt_upstream_connect_attempt_total 9850
telemt_upstream_connect_success_total 9805
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7614
telemt_me_reconnect_success_total 7576
telemt_me_reader_eof_total 8059
telemt_me_idle_close_by_peer_total 8059
telemt_me_route_drop_no_conn_total 118116
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372602
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1416
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 965
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7661
telemt_me_writer_restored_same_endpoint_total 7568
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 372606
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 4651113828 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 138039606812 (128.56 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 112
```