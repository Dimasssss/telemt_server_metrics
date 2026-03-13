# Server Metrics 2026-03-13 20:57:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 140318.2 (38h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4443353
telemt_connections_bad_total 37961
telemt_handshake_timeouts_total 106287
telemt_upstream_connect_attempt_total 29270
telemt_upstream_connect_success_total 29071
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6558
telemt_me_reconnect_attempts_total 29869
telemt_me_reconnect_success_total 19751
telemt_me_reader_eof_total 21195
telemt_me_idle_close_by_peer_total 21194
telemt_me_route_drop_no_conn_total 1673939
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4069150
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16185
telemt_desync_full_logged_total 4315
telemt_desync_suppressed_total 11870
telemt_desync_frames_bucket_total{bucket="1_2"} 4040
telemt_desync_frames_bucket_total{bucket="3_10"} 6173
telemt_desync_frames_bucket_total{bucket="gt_10"} 5972
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20349
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19738
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 4071285
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 60005167172 (55.88 GB)
telemt_user_octets_to_client{user="hello"} 1285730088309 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39982.1 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558053
telemt_connections_bad_total 41413
telemt_handshake_timeouts_total 12191
telemt_upstream_connect_attempt_total 11505
telemt_upstream_connect_success_total 11283
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 11505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1890
telemt_me_reconnect_attempts_total 10659
telemt_me_reconnect_success_total 7236
telemt_me_reader_eof_total 7657
telemt_me_idle_close_by_peer_total 7656
telemt_me_route_drop_no_conn_total 205897
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484348
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7448
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7228
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 486277
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 5228207173 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 155474215900 (144.80 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 169938.8 (47h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3233172
telemt_connections_bad_total 30082
telemt_handshake_timeouts_total 215886
telemt_upstream_connect_attempt_total 37791
telemt_upstream_connect_success_total 37770
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 37791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10230
telemt_me_reconnect_attempts_total 33941
telemt_me_reconnect_success_total 28996
telemt_me_reader_eof_total 30762
telemt_me_idle_close_by_peer_total 30761
telemt_me_route_drop_no_conn_total 1107937
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2681022
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8851
telemt_desync_full_logged_total 2968
telemt_desync_suppressed_total 5883
telemt_desync_frames_bucket_total{bucket="1_2"} 1463
telemt_desync_frames_bucket_total{bucket="3_10"} 3227
telemt_desync_frames_bucket_total{bucket="gt_10"} 4161
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29421
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 28955
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 2680300
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 44084986964 (41.06 GB)
telemt_user_octets_to_client{user="hello"} 946610160601 (881.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 169939.3 (47h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2100536
telemt_connections_bad_total 22790
telemt_handshake_timeouts_total 202255
telemt_upstream_connect_attempt_total 52846
telemt_upstream_connect_success_total 50406
telemt_upstream_connect_fail_total 2303
telemt_upstream_connect_attempts_per_request{bucket="1"} 52572
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2302
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43943
telemt_me_reconnect_success_total 34932
telemt_me_reader_eof_total 37499
telemt_me_idle_close_by_peer_total 37492
telemt_me_route_drop_no_conn_total 741228
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1728377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3701
telemt_desync_full_logged_total 1186
telemt_desync_suppressed_total 2515
telemt_desync_frames_bucket_total{bucket="1_2"} 983
telemt_desync_frames_bucket_total{bucket="3_10"} 1534
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35513
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34908
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 1734248
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 26931709731 (25.08 GB)
telemt_user_octets_to_client{user="hello"} 650106041658 (605.46 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39374.7 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595401
telemt_connections_bad_total 5797
telemt_handshake_timeouts_total 5579
telemt_upstream_connect_attempt_total 8642
telemt_upstream_connect_success_total 8359
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 8642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 31002
telemt_me_reconnect_success_total 6381
telemt_me_reader_eof_total 7273
telemt_me_idle_close_by_peer_total 7272
telemt_me_route_drop_no_conn_total 226175
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7209
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6377
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 559035
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 8339843884 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 177701695032 (165.50 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 56
```