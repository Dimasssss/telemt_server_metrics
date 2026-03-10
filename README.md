# Server Metrics 2026-03-10 20:42:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22507.0 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656953
telemt_connections_bad_total 8009
telemt_handshake_timeouts_total 7790
telemt_upstream_connect_attempt_total 4710
telemt_upstream_connect_success_total 4701
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 15165
telemt_me_reconnect_success_total 3513
telemt_me_reader_eof_total 3922
telemt_me_idle_close_by_peer_total 3922
telemt_me_route_drop_no_conn_total 274852
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619760
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3182
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 2317
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 1196
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3898
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3507
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 619569
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 8827952176 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 185907374660 (173.14 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22563.8 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289709
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17074
telemt_upstream_connect_attempt_total 11125
telemt_upstream_connect_success_total 8266
telemt_upstream_connect_fail_total 2859
telemt_upstream_connect_attempts_per_request{bucket="1"} 11125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2859
telemt_me_keepalive_timeout_total 1334
telemt_me_reconnect_attempts_total 4942
telemt_me_reconnect_success_total 4140
telemt_me_reader_eof_total 4329
telemt_me_idle_close_by_peer_total 4327
telemt_me_route_drop_no_conn_total 157304
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242489
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1367
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 1000
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 489
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4218
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4119
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 244752
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 2453095350 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 57523496892 (53.57 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22563.6 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468620
telemt_connections_bad_total 2512
telemt_handshake_timeouts_total 32632
telemt_upstream_connect_attempt_total 6669
telemt_upstream_connect_success_total 6571
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 12677
telemt_me_reconnect_success_total 4325
telemt_me_reader_eof_total 4708
telemt_me_idle_close_by_peer_total 4708
telemt_me_route_drop_no_conn_total 161595
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1349
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 974
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4660
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 4314
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 408538
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 5944379333 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 128934616149 (120.08 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22564.1 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317898
telemt_connections_bad_total 22088
telemt_handshake_timeouts_total 27312
telemt_upstream_connect_attempt_total 6124
telemt_upstream_connect_success_total 6124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 5966
telemt_me_reconnect_success_total 4948
telemt_me_reader_eof_total 5187
telemt_me_idle_close_by_peer_total 5187
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 103051
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256416
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5030
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4935
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 256114
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 3839085880 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 79833540544 (74.35 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22563.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335246
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 2105
telemt_upstream_connect_attempt_total 7106
telemt_upstream_connect_success_total 7077
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 9628
telemt_me_reconnect_success_total 5877
telemt_me_reader_eof_total 6141
telemt_me_idle_close_by_peer_total 6141
telemt_me_route_drop_no_conn_total 121540
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1834
telemt_desync_full_logged_total 686
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 703
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 6079
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 5877
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 315149
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 6049440424 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 104802716524 (97.61 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 66
```