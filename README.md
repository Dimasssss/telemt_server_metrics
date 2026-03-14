# Server Metrics 2026-03-14 08:02:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 180200.1 (50h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5093096
telemt_connections_bad_total 41704
telemt_handshake_timeouts_total 115911
telemt_upstream_connect_attempt_total 37957
telemt_upstream_connect_success_total 37709
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 37957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 7370
telemt_me_reconnect_attempts_total 37611
telemt_me_reconnect_success_total 26401
telemt_me_reader_eof_total 28342
telemt_me_idle_close_by_peer_total 28341
telemt_me_route_drop_no_conn_total 1926525
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4669530
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17793
telemt_desync_full_logged_total 4843
telemt_desync_suppressed_total 12950
telemt_desync_frames_bucket_total{bucket="1_2"} 4437
telemt_desync_frames_bucket_total{bucket="3_10"} 6758
telemt_desync_frames_bucket_total{bucket="gt_10"} 6598
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27133
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26388
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 4670980
telemt_user_connections_current{user="hello"} 1625
telemt_user_octets_from_client{user="hello"} 71590119060 (66.67 GB)
telemt_user_octets_to_client{user="hello"} 1495140369709 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79864.0 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873901
telemt_connections_bad_total 53910
telemt_handshake_timeouts_total 16013
telemt_upstream_connect_attempt_total 21451
telemt_upstream_connect_success_total 21173
telemt_upstream_connect_fail_total 278
telemt_upstream_connect_attempts_per_request{bucket="1"} 21451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 278
telemt_me_keepalive_timeout_total 2149
telemt_me_reconnect_attempts_total 18647
telemt_me_reconnect_success_total 15177
telemt_me_reader_eof_total 16127
telemt_me_idle_close_by_peer_total 16126
telemt_me_route_drop_no_conn_total 289025
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703291
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15506
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15169
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 705200
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 7391820333 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 243545674188 (226.82 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 209820.8 (58h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3640002
telemt_connections_bad_total 42680
telemt_handshake_timeouts_total 238978
telemt_upstream_connect_attempt_total 47444
telemt_upstream_connect_success_total 47422
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10722
telemt_me_reconnect_attempts_total 41638
telemt_me_reconnect_success_total 36655
telemt_me_reader_eof_total 38919
telemt_me_idle_close_by_peer_total 38918
telemt_me_route_drop_no_conn_total 1247524
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038251
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9994
telemt_desync_full_logged_total 3366
telemt_desync_suppressed_total 6628
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 3617
telemt_desync_frames_bucket_total{bucket="gt_10"} 4618
telemt_pool_swap_total 198
telemt_me_writer_removed_unexpected_total 37163
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36614
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 3037393
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 51245141804 (47.73 GB)
telemt_user_octets_to_client{user="hello"} 1087395238789 (1012.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 209823.2 (58h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2422026
telemt_connections_bad_total 23316
telemt_handshake_timeouts_total 293728
telemt_upstream_connect_attempt_total 65325
telemt_upstream_connect_success_total 62829
telemt_upstream_connect_fail_total 2359
telemt_upstream_connect_attempts_per_request{bucket="1"} 65051
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2358
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20545
telemt_me_reconnect_attempts_total 54436
telemt_me_reconnect_success_total 45354
telemt_me_reader_eof_total 48597
telemt_me_idle_close_by_peer_total 48590
telemt_me_route_drop_no_conn_total 813612
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1905547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3930
telemt_desync_full_logged_total 1280
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1081
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46027
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45330
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1911656
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 28643433503 (26.68 GB)
telemt_user_octets_to_client{user="hello"} 697510904626 (649.61 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79256.3 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850540
telemt_connections_bad_total 8772
telemt_handshake_timeouts_total 10060
telemt_upstream_connect_attempt_total 20146
telemt_upstream_connect_success_total 19607
telemt_upstream_connect_fail_total 538
telemt_upstream_connect_attempts_per_request{bucket="1"} 20145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 538
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 64845
telemt_me_reconnect_success_total 15664
telemt_me_reader_eof_total 17573
telemt_me_idle_close_by_peer_total 17572
telemt_me_route_drop_no_conn_total 326977
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794308
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1995
telemt_desync_full_logged_total 634
telemt_desync_suppressed_total 1361
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17335
telemt_me_refill_failed_total 1532
telemt_me_writer_restored_same_endpoint_total 15659
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1671
telemt_user_connections_total{user="hello"} 794166
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 14210100788 (13.23 GB)
telemt_user_octets_to_client{user="hello"} 266391806968 (248.10 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 92
```