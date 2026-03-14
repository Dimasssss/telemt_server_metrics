# Server Metrics 2026-03-14 09:08:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 184193.8 (51h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5236964
telemt_connections_bad_total 47673
telemt_handshake_timeouts_total 117936
telemt_upstream_connect_attempt_total 38685
telemt_upstream_connect_success_total 38434
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7490
telemt_me_reconnect_attempts_total 38161
telemt_me_reconnect_success_total 26948
telemt_me_reader_eof_total 28916
telemt_me_idle_close_by_peer_total 28915
telemt_me_route_drop_no_conn_total 1981291
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4799860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18354
telemt_desync_full_logged_total 5009
telemt_desync_suppressed_total 13345
telemt_desync_frames_bucket_total{bucket="1_2"} 4540
telemt_desync_frames_bucket_total{bucket="3_10"} 6986
telemt_desync_frames_bucket_total{bucket="gt_10"} 6828
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27692
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26935
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 4801324
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 73496766580 (68.45 GB)
telemt_user_octets_to_client{user="hello"} 1534666205085 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83857.9 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930307
telemt_connections_bad_total 54243
telemt_handshake_timeouts_total 18492
telemt_upstream_connect_attempt_total 22378
telemt_upstream_connect_success_total 22090
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2210
telemt_me_reconnect_attempts_total 23660
telemt_me_reconnect_success_total 15869
telemt_me_reader_eof_total 16960
telemt_me_idle_close_by_peer_total 16959
telemt_me_route_drop_no_conn_total 310773
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755385
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16339
telemt_me_refill_failed_total 237
telemt_me_writer_restored_same_endpoint_total 15861
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 757284
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 8082236377 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 261665741780 (243.70 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 213814.4 (59h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3734623
telemt_connections_bad_total 44503
telemt_handshake_timeouts_total 246408
telemt_upstream_connect_attempt_total 48299
telemt_upstream_connect_success_total 48278
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10873
telemt_me_reconnect_attempts_total 42317
telemt_me_reconnect_success_total 37327
telemt_me_reader_eof_total 39636
telemt_me_idle_close_by_peer_total 39635
telemt_me_route_drop_no_conn_total 1282102
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3118299
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10122
telemt_desync_full_logged_total 3439
telemt_desync_suppressed_total 6683
telemt_desync_frames_bucket_total{bucket="1_2"} 1792
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 37843
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37286
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 3117448
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 52700225376 (49.08 GB)
telemt_user_octets_to_client{user="hello"} 1112754991141 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 213817.1 (59h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2472706
telemt_connections_bad_total 23358
telemt_handshake_timeouts_total 304532
telemt_upstream_connect_attempt_total 66390
telemt_upstream_connect_success_total 63892
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66116
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20618
telemt_me_reconnect_attempts_total 57879
telemt_me_reconnect_success_total 46232
telemt_me_reader_eof_total 49569
telemt_me_idle_close_by_peer_total 49562
telemt_me_route_drop_no_conn_total 827610
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1942673
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3982
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2681
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46993
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46208
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1948830
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 29145761295 (27.14 GB)
telemt_user_octets_to_client{user="hello"} 706255722146 (657.75 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83250.9 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914094
telemt_connections_bad_total 12462
telemt_handshake_timeouts_total 11537
telemt_upstream_connect_attempt_total 21047
telemt_upstream_connect_success_total 20485
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 21047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_keepalive_timeout_total 1658
telemt_me_reconnect_attempts_total 66870
telemt_me_reconnect_success_total 16333
telemt_me_reader_eof_total 18315
telemt_me_idle_close_by_peer_total 18314
telemt_me_route_drop_no_conn_total 349461
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849776
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2228
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1528
telemt_desync_frames_bucket_total{bucket="1_2"} 716
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18061
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 16328
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1728
telemt_user_connections_total{user="hello"} 849696
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 15248736088 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 288396273892 (268.59 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 103
```