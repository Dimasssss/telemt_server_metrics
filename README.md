# Server Metrics 2026-03-15 13:08:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 53650.5 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1560436
telemt_connections_bad_total 89118
telemt_handshake_timeouts_total 13967
telemt_upstream_connect_attempt_total 10706
telemt_upstream_connect_success_total 10657
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12847
telemt_me_reconnect_success_total 7962
telemt_me_reader_eof_total 8530
telemt_me_idle_close_by_peer_total 8530
telemt_me_route_drop_no_conn_total 526942
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1315288
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4888
telemt_desync_full_logged_total 1384
telemt_desync_suppressed_total 3504
telemt_desync_frames_bucket_total{bucket="1_2"} 1231
telemt_desync_frames_bucket_total{bucket="3_10"} 1913
telemt_desync_frames_bucket_total{bucket="gt_10"} 1744
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8237
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7951
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 1314931
telemt_user_connections_current{user="hello"} 2361
telemt_user_octets_from_client{user="hello"} 18401811132 (17.14 GB)
telemt_user_octets_to_client{user="hello"} 522843470024 (486.94 GB)
telemt_user_unique_ips_current{user="hello"} 661
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 53651.2 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626552
telemt_connections_bad_total 32300
telemt_handshake_timeouts_total 40493
telemt_upstream_connect_attempt_total 13846
telemt_upstream_connect_success_total 13776
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10829
telemt_me_reconnect_success_total 10747
telemt_me_reader_eof_total 11358
telemt_me_idle_close_by_peer_total 11358
telemt_me_route_drop_no_conn_total 158714
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479172
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1890
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 712
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10870
telemt_me_writer_restored_same_endpoint_total 10735
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 479443
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 6693850619 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 179945589044 (167.59 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 53651.0 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274565
telemt_connections_bad_total 41316
telemt_handshake_timeouts_total 134605
telemt_upstream_connect_attempt_total 11902
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10383
telemt_me_reconnect_success_total 9135
telemt_me_reader_eof_total 9674
telemt_me_idle_close_by_peer_total 9674
telemt_me_route_drop_no_conn_total 375266
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2197
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 1401
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 828
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9292
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9116
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 838357
telemt_user_connections_current{user="hello"} 1387
telemt_user_octets_from_client{user="hello"} 12298774616 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 309962996128 (288.68 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 53651.0 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631804
telemt_connections_bad_total 67814
telemt_handshake_timeouts_total 34680
telemt_upstream_connect_attempt_total 49877
telemt_upstream_connect_success_total 49464
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 49877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 43964
telemt_me_reconnect_success_total 11757
telemt_me_reader_eof_total 13096
telemt_me_idle_close_by_peer_total 13096
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 166711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435762
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 859
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12874
telemt_me_refill_failed_total 1007
telemt_me_writer_restored_same_endpoint_total 11725
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1117
telemt_user_connections_total{user="hello"} 470645
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 8991473157 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 164021052880 (152.76 GB)
telemt_user_msgs_from_client{user="hello"} 638754
telemt_user_msgs_to_client{user="hello"} 2253569
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 53652.0 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668519
telemt_connections_bad_total 8912
telemt_handshake_timeouts_total 13573
telemt_upstream_connect_attempt_total 11930
telemt_upstream_connect_success_total 11868
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 12844
telemt_me_reconnect_success_total 9176
telemt_me_reader_eof_total 9827
telemt_me_idle_close_by_peer_total 9827
telemt_me_route_drop_no_conn_total 166184
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542221
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1363
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9399
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9168
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 542263
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 6947486816 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 201592891080 (187.75 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 108
```