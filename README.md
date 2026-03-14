# Server Metrics 2026-03-14 05:18:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 170372.8 (47h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4819112
telemt_connections_bad_total 40015
telemt_handshake_timeouts_total 110277
telemt_upstream_connect_attempt_total 35898
telemt_upstream_connect_success_total 35663
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 34987
telemt_me_reconnect_success_total 24842
telemt_me_reader_eof_total 26664
telemt_me_idle_close_by_peer_total 26663
telemt_me_route_drop_no_conn_total 1824992
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4421956
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17019
telemt_desync_full_logged_total 4601
telemt_desync_suppressed_total 12418
telemt_desync_frames_bucket_total{bucket="1_2"} 4245
telemt_desync_frames_bucket_total{bucket="3_10"} 6495
telemt_desync_frames_bucket_total{bucket="gt_10"} 6279
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 25511
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24829
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 4423508
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 64632194388 (60.19 GB)
telemt_user_octets_to_client{user="hello"} 1395724755269 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70036.5 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765037
telemt_connections_bad_total 53055
telemt_handshake_timeouts_total 14115
telemt_upstream_connect_attempt_total 19235
telemt_upstream_connect_success_total 18969
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 19235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 2113
telemt_me_reconnect_attempts_total 16917
telemt_me_reconnect_success_total 13460
telemt_me_reader_eof_total 14299
telemt_me_idle_close_by_peer_total 14298
telemt_me_route_drop_no_conn_total 251056
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604966
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1807
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1273
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13751
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13452
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 606917
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 6471019333 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 205184130628 (191.09 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 199993.2 (55h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3465730
telemt_connections_bad_total 37727
telemt_handshake_timeouts_total 229224
telemt_upstream_connect_attempt_total 45217
telemt_upstream_connect_success_total 45196
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10630
telemt_me_reconnect_attempts_total 39893
telemt_me_reconnect_success_total 34923
telemt_me_reader_eof_total 37103
telemt_me_idle_close_by_peer_total 37102
telemt_me_route_drop_no_conn_total 1184320
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2886666
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9546
telemt_desync_full_logged_total 3206
telemt_desync_suppressed_total 6340
telemt_desync_frames_bucket_total{bucket="1_2"} 1655
telemt_desync_frames_bucket_total{bucket="3_10"} 3459
telemt_desync_frames_bucket_total{bucket="gt_10"} 4432
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 35408
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34882
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 2885879
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 46270074540 (43.09 GB)
telemt_user_octets_to_client{user="hello"} 1035276289321 (964.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 199995.7 (55h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2322084
telemt_connections_bad_total 23121
telemt_handshake_timeouts_total 264929
telemt_upstream_connect_attempt_total 62464
telemt_upstream_connect_success_total 59985
telemt_upstream_connect_fail_total 2342
telemt_upstream_connect_attempts_per_request{bucket="1"} 62190
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2341
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20470
telemt_me_reconnect_attempts_total 52039
telemt_me_reconnect_success_total 42997
telemt_me_reader_eof_total 46112
telemt_me_idle_close_by_peer_total 46105
telemt_me_route_drop_no_conn_total 786829
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1839655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3886
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43654
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42973
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 657
telemt_user_connections_total{user="hello"} 1845632
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 27972888995 (26.05 GB)
telemt_user_octets_to_client{user="hello"} 676487505406 (630.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69428.9 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747642
telemt_connections_bad_total 8023
telemt_handshake_timeouts_total 8938
telemt_upstream_connect_attempt_total 18056
telemt_upstream_connect_success_total 17581
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 18056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 1545
telemt_me_reconnect_attempts_total 52891
telemt_me_reconnect_success_total 14095
telemt_me_reader_eof_total 15660
telemt_me_idle_close_by_peer_total 15659
telemt_me_route_drop_no_conn_total 285875
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697910
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15430
telemt_me_refill_failed_total 1208
telemt_me_writer_restored_same_endpoint_total 14090
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1335
telemt_user_connections_total{user="hello"} 697775
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 12550882176 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 231481555996 (215.58 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 33
```