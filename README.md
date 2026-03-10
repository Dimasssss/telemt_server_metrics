# Server Metrics 2026-03-10 20:47:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22812.7 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661180
telemt_connections_bad_total 8009
telemt_handshake_timeouts_total 7809
telemt_upstream_connect_attempt_total 4837
telemt_upstream_connect_success_total 4827
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 15248
telemt_me_reconnect_success_total 3595
telemt_me_reader_eof_total 4007
telemt_me_idle_close_by_peer_total 4007
telemt_me_route_drop_no_conn_total 277043
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623908
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3211
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 2340
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1212
telemt_desync_frames_bucket_total{bucket="gt_10"} 1098
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3983
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3589
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 623717
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 8868160312 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 187347806756 (174.48 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22869.7 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291715
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17109
telemt_upstream_connect_attempt_total 11211
telemt_upstream_connect_success_total 8352
telemt_upstream_connect_fail_total 2859
telemt_upstream_connect_attempts_per_request{bucket="1"} 11211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2859
telemt_me_keepalive_timeout_total 1335
telemt_me_reconnect_attempts_total 5009
telemt_me_reconnect_success_total 4207
telemt_me_reader_eof_total 4408
telemt_me_idle_close_by_peer_total 4406
telemt_me_route_drop_no_conn_total 157998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244325
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1393
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4287
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4186
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 246589
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 2484263710 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 57881826564 (53.91 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22869.5 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471846
telemt_connections_bad_total 2533
telemt_handshake_timeouts_total 32779
telemt_upstream_connect_attempt_total 6723
telemt_upstream_connect_success_total 6623
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 6723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 14085
telemt_me_reconnect_success_total 4357
telemt_me_reader_eof_total 4783
telemt_me_idle_close_by_peer_total 4783
telemt_me_route_drop_no_conn_total 163350
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410664
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1357
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4735
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 4346
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 411607
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 5968524933 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 130260934249 (121.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22869.8 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320287
telemt_connections_bad_total 22363
telemt_handshake_timeouts_total 27533
telemt_upstream_connect_attempt_total 6218
telemt_upstream_connect_success_total 6217
telemt_upstream_connect_attempts_per_request{bucket="1"} 6217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 6040
telemt_me_reconnect_success_total 5021
telemt_me_reader_eof_total 5269
telemt_me_idle_close_by_peer_total 5269
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 104129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258259
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5104
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5008
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 257947
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 3851545872 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 80346903912 (74.83 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22869.7 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338745
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 2111
telemt_upstream_connect_attempt_total 7215
telemt_upstream_connect_success_total 7186
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 9715
telemt_me_reconnect_success_total 5964
telemt_me_reader_eof_total 6245
telemt_me_idle_close_by_peer_total 6245
telemt_me_route_drop_no_conn_total 122547
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318455
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1852
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6166
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 5964
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 318352
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 6072361240 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 106119846236 (98.83 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 66
```