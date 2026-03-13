# Server Metrics 2026-03-13 19:40:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 135733.9 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4332231
telemt_connections_bad_total 37799
telemt_handshake_timeouts_total 105608
telemt_upstream_connect_attempt_total 28434
telemt_upstream_connect_success_total 28241
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 28434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 6526
telemt_me_reconnect_attempts_total 29258
telemt_me_reconnect_success_total 19142
telemt_me_reader_eof_total 20548
telemt_me_idle_close_by_peer_total 20547
telemt_me_route_drop_no_conn_total 1628427
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3962309
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15580
telemt_desync_full_logged_total 4158
telemt_desync_suppressed_total 11422
telemt_desync_frames_bucket_total{bucket="1_2"} 3876
telemt_desync_frames_bucket_total{bucket="3_10"} 5943
telemt_desync_frames_bucket_total{bucket="gt_10"} 5761
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19734
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19129
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 3964471
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 57445116144 (53.50 GB)
telemt_user_octets_to_client{user="hello"} 1249429563233 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35397.8 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512028
telemt_connections_bad_total 39844
telemt_handshake_timeouts_total 11126
telemt_upstream_connect_attempt_total 10369
telemt_upstream_connect_success_total 10155
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1868
telemt_me_reconnect_attempts_total 9745
telemt_me_reconnect_success_total 6330
telemt_me_reader_eof_total 6697
telemt_me_idle_close_by_peer_total 6696
telemt_me_route_drop_no_conn_total 191736
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444957
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1542
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 1128
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6523
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6322
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 446887
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 4761322433 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 141081556880 (131.39 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 165354.5 (45h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3164015
telemt_connections_bad_total 29294
telemt_handshake_timeouts_total 212906
telemt_upstream_connect_attempt_total 36681
telemt_upstream_connect_success_total 36666
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10185
telemt_me_reconnect_attempts_total 30683
telemt_me_reconnect_success_total 28120
telemt_me_reader_eof_total 29805
telemt_me_idle_close_by_peer_total 29804
telemt_me_route_drop_no_conn_total 1082736
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2617038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8730
telemt_desync_full_logged_total 2890
telemt_desync_suppressed_total 5840
telemt_desync_frames_bucket_total{bucket="1_2"} 1438
telemt_desync_frames_bucket_total{bucket="3_10"} 3193
telemt_desync_frames_bucket_total{bucket="gt_10"} 4099
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 28457
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28079
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 2616323
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 43336123616 (40.36 GB)
telemt_user_octets_to_client{user="hello"} 920322662597 (857.12 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 165355.2 (45h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041044
telemt_connections_bad_total 22122
telemt_handshake_timeouts_total 187238
telemt_upstream_connect_attempt_total 51905
telemt_upstream_connect_success_total 49470
telemt_upstream_connect_fail_total 2298
telemt_upstream_connect_attempts_per_request{bucket="1"} 51631
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2297
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20186
telemt_me_reconnect_attempts_total 43222
telemt_me_reconnect_success_total 34215
telemt_me_reader_eof_total 36728
telemt_me_idle_close_by_peer_total 36721
telemt_me_route_drop_no_conn_total 724202
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1685826
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3621
telemt_desync_full_logged_total 1153
telemt_desync_suppressed_total 2468
telemt_desync_frames_bucket_total{bucket="1_2"} 953
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1161
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 34783
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34191
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 1691695
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 25925023727 (24.14 GB)
telemt_user_octets_to_client{user="hello"} 638068951322 (594.25 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34790.9 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552587
telemt_connections_bad_total 5666
telemt_handshake_timeouts_total 5427
telemt_upstream_connect_attempt_total 7495
telemt_upstream_connect_success_total 7251
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 7495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 960
telemt_me_reconnect_attempts_total 26432
telemt_me_reconnect_success_total 5496
telemt_me_reader_eof_total 6257
telemt_me_idle_close_by_peer_total 6256
telemt_me_route_drop_no_conn_total 209666
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517660
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1456
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6193
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5492
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 517631
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 6024842468 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 165766970452 (154.38 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 78
```