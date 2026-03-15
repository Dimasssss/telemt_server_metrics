# Server Metrics 2026-03-15 06:40:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 30366.2 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489318
telemt_connections_bad_total 8641
telemt_handshake_timeouts_total 3227
telemt_upstream_connect_attempt_total 6382
telemt_upstream_connect_success_total 6356
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4868
telemt_me_reconnect_success_total 4844
telemt_me_reader_eof_total 5119
telemt_me_idle_close_by_peer_total 5119
telemt_me_route_drop_no_conn_total 150157
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415978
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1094
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4899
telemt_me_writer_restored_same_endpoint_total 4833
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 415987
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 4770709852 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 147407084428 (137.28 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 30367.2 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177473
telemt_connections_bad_total 18320
telemt_handshake_timeouts_total 5522
telemt_upstream_connect_attempt_total 8584
telemt_upstream_connect_success_total 8540
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6745
telemt_me_reconnect_success_total 6710
telemt_me_reader_eof_total 7103
telemt_me_idle_close_by_peer_total 7103
telemt_me_route_drop_no_conn_total 44643
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148380
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6736
telemt_me_writer_restored_same_endpoint_total 6702
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 148672
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 2433281775 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 54491907468 (50.75 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 30367.2 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326208
telemt_connections_bad_total 8907
telemt_handshake_timeouts_total 30649
telemt_upstream_connect_attempt_total 7021
telemt_upstream_connect_success_total 6989
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5495
telemt_me_reconnect_success_total 5466
telemt_me_reader_eof_total 5781
telemt_me_idle_close_by_peer_total 5781
telemt_me_route_drop_no_conn_total 83618
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272533
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 509
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5524
telemt_me_writer_restored_same_endpoint_total 5447
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 272321
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 4251691016 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 113674499048 (105.87 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 30367.0 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224597
telemt_connections_bad_total 40645
telemt_handshake_timeouts_total 14422
telemt_upstream_connect_attempt_total 10311
telemt_upstream_connect_success_total 10080
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 10311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 17116
telemt_me_reconnect_success_total 8562
telemt_me_reader_eof_total 9103
telemt_me_idle_close_by_peer_total 9103
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 53749
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164877
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8901
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 8536
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 164880
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 1403999900 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 57614822336 (53.66 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 30368.6 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163531
telemt_connections_bad_total 247
telemt_handshake_timeouts_total 1598
telemt_upstream_connect_attempt_total 6813
telemt_upstream_connect_success_total 6785
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5295
telemt_me_reconnect_success_total 5272
telemt_me_reader_eof_total 5625
telemt_me_idle_close_by_peer_total 5625
telemt_me_route_drop_no_conn_total 48147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5323
telemt_me_writer_restored_same_endpoint_total 5264
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 153572
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 1488895504 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 55126747712 (51.34 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 82
```