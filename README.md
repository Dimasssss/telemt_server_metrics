# Server Metrics 2026-03-12 12:42:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24238.0 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830000
telemt_connections_bad_total 2417
telemt_handshake_timeouts_total 6457
telemt_upstream_connect_attempt_total 4807
telemt_upstream_connect_success_total 4778
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 7440
telemt_me_reconnect_success_total 3545
telemt_me_reader_eof_total 3804
telemt_me_idle_close_by_peer_total 3804
telemt_me_route_drop_no_conn_total 294189
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4185
telemt_desync_full_logged_total 1061
telemt_desync_suppressed_total 3124
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 1516
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3704
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3532
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 797251
telemt_user_connections_current{user="hello"} 1652
telemt_user_octets_from_client{user="hello"} 13573497456 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 227412503696 (211.79 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53858.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417048
telemt_connections_bad_total 5126
telemt_handshake_timeouts_total 22144
telemt_upstream_connect_attempt_total 13035
telemt_upstream_connect_success_total 13028
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1055
telemt_me_reconnect_attempts_total 10225
telemt_me_reconnect_success_total 10168
telemt_me_reader_eof_total 10813
telemt_me_idle_close_by_peer_total 10813
telemt_me_route_drop_no_conn_total 119825
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1205
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 815
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10262
telemt_me_writer_restored_same_endpoint_total 10159
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 368074
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 4915177295 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 130646023754 (121.67 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53858.4 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937044
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 70415
telemt_upstream_connect_attempt_total 13133
telemt_upstream_connect_success_total 13128
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 863
telemt_me_reconnect_attempts_total 10181
telemt_me_reconnect_success_total 10092
telemt_me_reader_eof_total 10628
telemt_me_idle_close_by_peer_total 10628
telemt_me_route_drop_no_conn_total 231358
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644970
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2929
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 2050
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 1038
telemt_desync_frames_bucket_total{bucket="gt_10"} 1473
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10121
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10051
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 645198
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 8410642940 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 202909313585 (188.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53858.9 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525533
telemt_connections_bad_total 7637
telemt_handshake_timeouts_total 48433
telemt_upstream_connect_attempt_total 14455
telemt_upstream_connect_success_total 14397
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1268
telemt_me_reconnect_attempts_total 12947
telemt_me_reconnect_success_total 11715
telemt_me_reader_eof_total 12433
telemt_me_idle_close_by_peer_total 12433
telemt_me_route_drop_no_conn_total 173217
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 885
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11839
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11694
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 438753
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 4989530332 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 172372757420 (160.53 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53858.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591896
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 4692
telemt_upstream_connect_attempt_total 17325
telemt_upstream_connect_success_total 17116
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 17325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 967
telemt_me_reconnect_attempts_total 21652
telemt_me_reconnect_success_total 14428
telemt_me_reader_eof_total 15130
telemt_me_idle_close_by_peer_total 15130
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 199124
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553147
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2316
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1535
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 841
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14794
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14401
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 553060
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 6393441768 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 141171309336 (131.48 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 118
```