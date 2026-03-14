# Server Metrics 2026-03-14 07:31:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 178357.6 (49h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5031359
telemt_connections_bad_total 40350
telemt_handshake_timeouts_total 114820
telemt_upstream_connect_attempt_total 37434
telemt_upstream_connect_success_total 37190
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 37434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 7345
telemt_me_reconnect_attempts_total 36123
telemt_me_reconnect_success_total 25971
telemt_me_reader_eof_total 27855
telemt_me_idle_close_by_peer_total 27854
telemt_me_route_drop_no_conn_total 1904326
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4615377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17552
telemt_desync_full_logged_total 4778
telemt_desync_suppressed_total 12774
telemt_desync_frames_bucket_total{bucket="1_2"} 4383
telemt_desync_frames_bucket_total{bucket="3_10"} 6681
telemt_desync_frames_bucket_total{bucket="gt_10"} 6488
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26659
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25958
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 688
telemt_user_connections_total{user="hello"} 4616856
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 69892683424 (65.09 GB)
telemt_user_octets_to_client{user="hello"} 1466525617021 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78021.5 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851427
telemt_connections_bad_total 53895
telemt_handshake_timeouts_total 15483
telemt_upstream_connect_attempt_total 21010
telemt_upstream_connect_success_total 20737
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 21010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 2146
telemt_me_reconnect_attempts_total 18297
telemt_me_reconnect_success_total 14831
telemt_me_reader_eof_total 15765
telemt_me_idle_close_by_peer_total 15764
telemt_me_route_drop_no_conn_total 280524
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681965
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2012
telemt_desync_full_logged_total 622
telemt_desync_suppressed_total 1390
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15151
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14823
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 683879
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 7171120309 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 235048123960 (218.91 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 207978.3 (57h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3605249
telemt_connections_bad_total 42319
telemt_handshake_timeouts_total 236598
telemt_upstream_connect_attempt_total 46896
telemt_upstream_connect_success_total 46875
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10710
telemt_me_reconnect_attempts_total 41192
telemt_me_reconnect_success_total 36214
telemt_me_reader_eof_total 38468
telemt_me_idle_close_by_peer_total 38467
telemt_me_route_drop_no_conn_total 1234189
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3007592
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9908
telemt_desync_full_logged_total 3328
telemt_desync_suppressed_total 6580
telemt_desync_frames_bucket_total{bucket="1_2"} 1736
telemt_desync_frames_bucket_total{bucket="3_10"} 3584
telemt_desync_frames_bucket_total{bucket="gt_10"} 4588
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36717
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36173
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 3006747
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 50251265896 (46.80 GB)
telemt_user_octets_to_client{user="hello"} 1073575097389 (999.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 207980.9 (57h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2399567
telemt_connections_bad_total 23306
telemt_handshake_timeouts_total 288297
telemt_upstream_connect_attempt_total 64920
telemt_upstream_connect_success_total 62429
telemt_upstream_connect_fail_total 2354
telemt_upstream_connect_attempts_per_request{bucket="1"} 64646
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2353
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20529
telemt_me_reconnect_attempts_total 54137
telemt_me_reconnect_success_total 45057
telemt_me_reader_eof_total 48259
telemt_me_idle_close_by_peer_total 48252
telemt_me_route_drop_no_conn_total 807017
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1889733
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3928
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1079
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45728
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45033
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 671
telemt_user_connections_total{user="hello"} 1895827
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 28461180995 (26.51 GB)
telemt_user_octets_to_client{user="hello"} 694706373726 (647.00 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77414.7 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823816
telemt_connections_bad_total 8338
telemt_handshake_timeouts_total 9753
telemt_upstream_connect_attempt_total 19783
telemt_upstream_connect_success_total 19254
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 19783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 1589
telemt_me_reconnect_attempts_total 62034
telemt_me_reconnect_success_total 15414
telemt_me_reader_eof_total 17237
telemt_me_idle_close_by_peer_total 17236
telemt_me_route_drop_no_conn_total 317450
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769660
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1921
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16999
telemt_me_refill_failed_total 1452
telemt_me_writer_restored_same_endpoint_total 15409
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1585
telemt_user_connections_total{user="hello"} 769519
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 13692296192 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 259148645152 (241.35 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 87
```