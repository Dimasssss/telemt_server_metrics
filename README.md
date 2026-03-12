# Server Metrics 2026-03-12 13:43:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27908.6 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 977294
telemt_connections_bad_total 10068
telemt_handshake_timeouts_total 9282
telemt_upstream_connect_attempt_total 5458
telemt_upstream_connect_success_total 5424
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 7912
telemt_me_reconnect_success_total 4014
telemt_me_reader_eof_total 4297
telemt_me_idle_close_by_peer_total 4296
telemt_me_route_drop_no_conn_total 344575
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4950
telemt_desync_full_logged_total 1248
telemt_desync_suppressed_total 3702
telemt_desync_frames_bucket_total{bucket="1_2"} 1238
telemt_desync_frames_bucket_total{bucket="3_10"} 1787
telemt_desync_frames_bucket_total{bucket="gt_10"} 1925
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4181
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4001
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 929036
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 15520087780 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 277004505392 (257.98 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57529.2 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471092
telemt_connections_bad_total 5312
telemt_handshake_timeouts_total 24853
telemt_upstream_connect_attempt_total 13832
telemt_upstream_connect_success_total 13825
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1111
telemt_me_reconnect_attempts_total 10846
telemt_me_reconnect_success_total 10786
telemt_me_reader_eof_total 11470
telemt_me_idle_close_by_peer_total 11470
telemt_me_route_drop_no_conn_total 135666
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1430
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10885
telemt_me_writer_restored_same_endpoint_total 10777
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 417756
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 6476896355 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 151722222590 (141.30 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57529.0 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028356
telemt_connections_bad_total 5470
telemt_handshake_timeouts_total 76373
telemt_upstream_connect_attempt_total 13781
telemt_upstream_connect_success_total 13776
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 922
telemt_me_reconnect_attempts_total 10655
telemt_me_reconnect_success_total 10559
telemt_me_reader_eof_total 11122
telemt_me_idle_close_by_peer_total 11122
telemt_me_route_drop_no_conn_total 263800
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727988
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3139
telemt_desync_full_logged_total 953
telemt_desync_suppressed_total 2186
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 1137
telemt_desync_frames_bucket_total{bucket="gt_10"} 1552
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10593
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10518
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 728187
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 9537977240 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 236754566545 (220.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57529.7 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590512
telemt_connections_bad_total 7673
telemt_handshake_timeouts_total 54415
telemt_upstream_connect_attempt_total 15301
telemt_upstream_connect_success_total 15239
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 13611
telemt_me_reconnect_success_total 12378
telemt_me_reader_eof_total 13123
telemt_me_idle_close_by_peer_total 13123
telemt_me_route_drop_no_conn_total 198760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1010
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 417
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12512
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12357
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 496808
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 5507963544 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 200639352244 (186.86 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57529.4 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666116
telemt_connections_bad_total 1746
telemt_handshake_timeouts_total 5405
telemt_upstream_connect_attempt_total 18206
telemt_upstream_connect_success_total 17987
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 18206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 1021
telemt_me_reconnect_attempts_total 22350
telemt_me_reconnect_success_total 15123
telemt_me_reader_eof_total 15853
telemt_me_idle_close_by_peer_total 15853
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 226866
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619971
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2578
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 1713
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 955
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15497
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15094
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 619881
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 7160560868 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 168048818992 (156.51 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 110
```