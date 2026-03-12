# Server Metrics 2026-03-12 10:24:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15973.1 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520821
telemt_connections_bad_total 1467
telemt_handshake_timeouts_total 2841
telemt_upstream_connect_attempt_total 3123
telemt_upstream_connect_success_total 3103
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 6163
telemt_me_reconnect_success_total 2278
telemt_me_reader_eof_total 2470
telemt_me_idle_close_by_peer_total 2470
telemt_me_route_drop_no_conn_total 180055
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504508
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2400
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1801
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 884
telemt_desync_frames_bucket_total{bucket="gt_10"} 907
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2420
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2265
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 504374
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 7979714424 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 137627383288 (128.18 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45593.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295052
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 8533
telemt_upstream_connect_attempt_total 11499
telemt_upstream_connect_success_total 11493
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 674
telemt_me_reconnect_attempts_total 9081
telemt_me_reconnect_success_total 9034
telemt_me_reader_eof_total 9600
telemt_me_idle_close_by_peer_total 9600
telemt_me_route_drop_no_conn_total 85715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 524
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9109
telemt_me_writer_restored_same_endpoint_total 9025
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 264727
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 3632718643 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 96355310614 (89.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45593.5 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744799
telemt_connections_bad_total 3704
telemt_handshake_timeouts_total 54395
telemt_upstream_connect_attempt_total 11488
telemt_upstream_connect_success_total 11483
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 8930
telemt_me_reconnect_success_total 8855
telemt_me_reader_eof_total 9303
telemt_me_idle_close_by_peer_total 9303
telemt_me_route_drop_no_conn_total 166485
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473687
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1500
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1120
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8865
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8814
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 473939
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 5633895504 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 153890088697 (143.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45593.9 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381584
telemt_connections_bad_total 2469
telemt_handshake_timeouts_total 28734
telemt_upstream_connect_attempt_total 12344
telemt_upstream_connect_success_total 12294
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 841
telemt_me_reconnect_attempts_total 10054
telemt_me_reconnect_success_total 10017
telemt_me_reader_eof_total 10626
telemt_me_idle_close_by_peer_total 10626
telemt_me_route_drop_no_conn_total 128846
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 673
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10082
telemt_me_writer_restored_same_endpoint_total 9996
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 321678
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 3895217268 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 125405828824 (116.79 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45593.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431336
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 3269
telemt_upstream_connect_attempt_total 14788
telemt_upstream_connect_success_total 14615
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 627
telemt_me_reconnect_attempts_total 13852
telemt_me_reconnect_success_total 12328
telemt_me_reader_eof_total 12843
telemt_me_idle_close_by_peer_total 12843
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 139410
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406699
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1716
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12496
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12306
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 406624
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 4534475948 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 97947688828 (91.22 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 109
```