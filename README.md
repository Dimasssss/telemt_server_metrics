# Server Metrics 2026-03-14 12:48:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 197392.9 (54h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5738827
telemt_connections_bad_total 64832
telemt_handshake_timeouts_total 126622
telemt_upstream_connect_attempt_total 41422
telemt_upstream_connect_success_total 41156
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 41422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 7869
telemt_me_reconnect_attempts_total 47924
telemt_me_reconnect_success_total 28987
telemt_me_reader_eof_total 31250
telemt_me_idle_close_by_peer_total 31249
telemt_me_route_drop_no_conn_total 2174893
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5261534
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20298
telemt_desync_full_logged_total 5560
telemt_desync_suppressed_total 14738
telemt_desync_frames_bucket_total{bucket="1_2"} 4890
telemt_desync_frames_bucket_total{bucket="3_10"} 7712
telemt_desync_frames_bucket_total{bucket="gt_10"} 7696
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29999
telemt_me_refill_failed_total 586
telemt_me_writer_restored_same_endpoint_total 28974
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1012
telemt_user_connections_total{user="hello"} 5263121
telemt_user_connections_current{user="hello"} 1807
telemt_user_octets_from_client{user="hello"} 82181378300 (76.54 GB)
telemt_user_octets_to_client{user="hello"} 1675603568477 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97056.6 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120427
telemt_connections_bad_total 58965
telemt_handshake_timeouts_total 26536
telemt_upstream_connect_attempt_total 24705
telemt_upstream_connect_success_total 24398
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2426
telemt_me_reconnect_attempts_total 37952
telemt_me_reconnect_success_total 17542
telemt_me_reader_eof_total 19072
telemt_me_idle_close_by_peer_total 19071
telemt_me_route_drop_no_conn_total 379647
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924858
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2576
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1767
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1073
telemt_desync_frames_bucket_total{bucket="gt_10"} 832
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18428
telemt_me_refill_failed_total 631
telemt_me_writer_restored_same_endpoint_total 17534
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 886
telemt_user_connections_total{user="hello"} 926773
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 10216232361 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 330475816168 (307.78 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 227013.6 (63h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4069474
telemt_connections_bad_total 46583
telemt_handshake_timeouts_total 282150
telemt_upstream_connect_attempt_total 51107
telemt_upstream_connect_success_total 51085
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 262
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11335
telemt_me_reconnect_attempts_total 45445
telemt_me_reconnect_success_total 39436
telemt_me_reader_eof_total 41879
telemt_me_idle_close_by_peer_total 41877
telemt_me_route_drop_no_conn_total 1398392
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3403389
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10865
telemt_desync_full_logged_total 3671
telemt_desync_suppressed_total 7194
telemt_desync_frames_bucket_total{bucket="1_2"} 1998
telemt_desync_frames_bucket_total{bucket="3_10"} 3911
telemt_desync_frames_bucket_total{bucket="gt_10"} 4956
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40021
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39395
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 3402527
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 58037586800 (54.05 GB)
telemt_user_octets_to_client{user="hello"} 1213077035401 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 227015.8 (63h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2653261
telemt_connections_bad_total 23515
telemt_handshake_timeouts_total 345310
telemt_upstream_connect_attempt_total 69893
telemt_upstream_connect_success_total 67383
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69619
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21009
telemt_me_reconnect_attempts_total 61823
telemt_me_reconnect_success_total 49038
telemt_me_reader_eof_total 52539
telemt_me_idle_close_by_peer_total 52531
telemt_me_route_drop_no_conn_total 879607
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2071772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 49866
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49013
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 2078302
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 30705711403 (28.60 GB)
telemt_user_octets_to_client{user="hello"} 738477337962 (687.76 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96449.6 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108628
telemt_connections_bad_total 18174
telemt_handshake_timeouts_total 14226
telemt_upstream_connect_attempt_total 23093
telemt_upstream_connect_success_total 22433
telemt_upstream_connect_fail_total 660
telemt_upstream_connect_attempts_per_request{bucket="1"} 23093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 660
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 87157
telemt_me_reconnect_success_total 17607
telemt_me_reader_eof_total 20188
telemt_me_idle_close_by_peer_total 20187
telemt_me_route_drop_no_conn_total 447013
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026928
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2725
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 1870
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 953
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19939
telemt_me_refill_failed_total 2168
telemt_me_writer_restored_same_endpoint_total 17602
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2332
telemt_user_connections_total{user="hello"} 1026117
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 17863183704 (16.64 GB)
telemt_user_octets_to_client{user="hello"} 345474862904 (321.75 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 100
```