# Server Metrics 2026-03-13 20:11:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 137567.9 (38h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4379508
telemt_connections_bad_total 37844
telemt_handshake_timeouts_total 105940
telemt_upstream_connect_attempt_total 28814
telemt_upstream_connect_success_total 28618
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 28814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6549
telemt_me_reconnect_attempts_total 29546
telemt_me_reconnect_success_total 19430
telemt_me_reader_eof_total 20849
telemt_me_idle_close_by_peer_total 20848
telemt_me_route_drop_no_conn_total 1647645
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4007776
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15864
telemt_desync_full_logged_total 4228
telemt_desync_suppressed_total 11636
telemt_desync_frames_bucket_total{bucket="1_2"} 3953
telemt_desync_frames_bucket_total{bucket="3_10"} 6046
telemt_desync_frames_bucket_total{bucket="gt_10"} 5865
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 20024
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19417
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 4009940
telemt_user_connections_current{user="hello"} 1193
telemt_user_octets_from_client{user="hello"} 58510359056 (54.49 GB)
telemt_user_octets_to_client{user="hello"} 1265215595309 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37231.6 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533662
telemt_connections_bad_total 41294
telemt_handshake_timeouts_total 12061
telemt_upstream_connect_attempt_total 10764
telemt_upstream_connect_success_total 10548
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 10764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 1873
telemt_me_reconnect_attempts_total 10052
telemt_me_reconnect_success_total 6634
telemt_me_reader_eof_total 7014
telemt_me_idle_close_by_peer_total 7013
telemt_me_route_drop_no_conn_total 198515
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462597
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1562
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6833
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6626
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 464527
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 4964762717 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 146842355936 (136.76 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 167188.3 (46h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3193204
telemt_connections_bad_total 29612
telemt_handshake_timeouts_total 213819
telemt_upstream_connect_attempt_total 37065
telemt_upstream_connect_success_total 37047
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 37065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 10193
telemt_me_reconnect_attempts_total 30980
telemt_me_reconnect_success_total 28411
telemt_me_reader_eof_total 30103
telemt_me_idle_close_by_peer_total 30102
telemt_me_route_drop_no_conn_total 1093614
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2644437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8763
telemt_desync_full_logged_total 2910
telemt_desync_suppressed_total 5853
telemt_desync_frames_bucket_total{bucket="1_2"} 1443
telemt_desync_frames_bucket_total{bucket="3_10"} 3205
telemt_desync_frames_bucket_total{bucket="gt_10"} 4115
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28753
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28370
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 2643719
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 43621060668 (40.63 GB)
telemt_user_octets_to_client{user="hello"} 930940334849 (867.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 167188.9 (46h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2068155
telemt_connections_bad_total 22616
telemt_handshake_timeouts_total 194727
telemt_upstream_connect_attempt_total 52287
telemt_upstream_connect_success_total 49850
telemt_upstream_connect_fail_total 2300
telemt_upstream_connect_attempts_per_request{bucket="1"} 52013
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2299
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20202
telemt_me_reconnect_attempts_total 43516
telemt_me_reconnect_success_total 34508
telemt_me_reader_eof_total 37045
telemt_me_idle_close_by_peer_total 37038
telemt_me_route_drop_no_conn_total 731123
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1704647
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3684
telemt_desync_full_logged_total 1177
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 35082
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34484
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 1710516
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 26301288155 (24.49 GB)
telemt_user_octets_to_client{user="hello"} 642322703178 (598.21 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36624.4 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571938
telemt_connections_bad_total 5703
telemt_handshake_timeouts_total 5491
telemt_upstream_connect_attempt_total 8080
telemt_upstream_connect_success_total 7814
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 8080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 967
telemt_me_reconnect_attempts_total 26909
telemt_me_reconnect_success_total 5970
telemt_me_reader_eof_total 6738
telemt_me_idle_close_by_peer_total 6737
telemt_me_route_drop_no_conn_total 216890
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536396
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1013
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 590
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6674
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5966
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 704
telemt_user_connections_total{user="hello"} 536346
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 6259485816 (5.83 GB)
telemt_user_octets_to_client{user="hello"} 171171747980 (159.42 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 79
```